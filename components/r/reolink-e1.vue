<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajcl8c7el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajcl8c7el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:reolink-e1" /></template>
