<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euj3uvbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="euj3uvbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:settings-alt-2-fill" /></template>
