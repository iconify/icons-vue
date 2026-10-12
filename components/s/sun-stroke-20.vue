<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkfscribz.css';
import '../../css/e/epuqqhiuz.css';
import '../../css/b/bis6shb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kkfscribz"/><path class="epuqqhiuz"/><path class="bis6shb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sun-stroke-20" /></template>
