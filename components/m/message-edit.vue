<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahf8b4gpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahf8b4gpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:message-edit" /></template>
