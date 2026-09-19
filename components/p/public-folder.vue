<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaw53egrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="eaw53egrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:public-folder" /></template>
