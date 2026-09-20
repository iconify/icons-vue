<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkiig2blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkiig2blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:youtube" /></template>
