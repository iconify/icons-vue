<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq7duib7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq7duib7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:settings-fill" /></template>
