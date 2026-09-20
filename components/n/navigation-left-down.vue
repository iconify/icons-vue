<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/f/fay9zd.css';
import '../../css/m/msxztt.css';
import '../../css/s/so-from-26.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c fay9zd"/><path class="a0m25c msxztt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:navigation-left-down" /></template>
