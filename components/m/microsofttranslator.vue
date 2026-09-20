<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kigko6rhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kigko6rhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:microsofttranslator" /></template>
