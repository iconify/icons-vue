<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho7y_mbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ho7y_mbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:snowmobile" /></template>
