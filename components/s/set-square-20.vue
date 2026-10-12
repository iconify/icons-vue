<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqcluhbqi.css';
import '../../css/q/qn6jbqb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fqcluhbqi"/><path class="qn6jbqb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:set-square-20" /></template>
