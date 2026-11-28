<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afjdefi9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afjdefi9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:progress" /></template>
