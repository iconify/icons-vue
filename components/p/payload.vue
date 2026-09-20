<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd8k0c7fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd8k0c7fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:payload" /></template>
