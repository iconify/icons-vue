<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe5lveblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe5lveblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wifi-connected-03" /></template>
