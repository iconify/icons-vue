<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glles2bcn.css';
import '../../css/a/aeily0buk.css';
import '../../css/f/f3_ob3l1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="glles2bcn"/><path class="aeily0buk"/><path class="f3_ob3l1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:vegetation-asset" /></template>
