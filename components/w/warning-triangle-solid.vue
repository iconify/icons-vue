<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba6a_pbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ba6a_pbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:warning-triangle-solid" /></template>
