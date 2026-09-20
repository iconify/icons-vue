<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi0agm_ih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi0agm_ih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:paragraph" /></template>
