<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bibvwrb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bibvwrb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mail-shield-solid" /></template>
