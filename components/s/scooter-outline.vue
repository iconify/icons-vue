<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5712_bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o5712_bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scooter-outline" /></template>
