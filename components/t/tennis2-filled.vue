<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tby6k6z2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tby6k6z2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tennis2-filled" /></template>
