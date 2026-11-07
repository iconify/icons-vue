<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh9ph61iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dh9ph61iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:vanity-outline" /></template>
