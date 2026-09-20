<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jztotk7yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jztotk7yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:phone-enabled-line" /></template>
