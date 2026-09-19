<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvf9yc10o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uvf9yc10o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sun-haze" /></template>
