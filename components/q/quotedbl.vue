<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp_ca1b9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":262,"height":723};
const content = `<path class="mp_ca1b9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:quotedbl" /></template>
