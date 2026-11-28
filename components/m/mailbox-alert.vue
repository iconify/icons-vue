<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6umypz9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6umypz9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mailbox-alert" /></template>
