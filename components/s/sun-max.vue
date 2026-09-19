<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzk6tjbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hzk6tjbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sun-max" /></template>
