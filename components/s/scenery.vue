<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvaty4zot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvaty4zot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:scenery" /></template>
