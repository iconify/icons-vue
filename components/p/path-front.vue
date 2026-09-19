<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbll2ccxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wbll2ccxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:path-front" /></template>
