<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rja9fwbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rja9fwbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:youtube" /></template>
