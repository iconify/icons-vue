<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho_nvabvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho_nvabvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nubank" /></template>
