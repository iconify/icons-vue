<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf4nzsadg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nf4nzsadg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:meetup-logo-block" /></template>
