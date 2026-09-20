<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg8-oacpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg8-oacpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:refresh-ccw-fill" /></template>
