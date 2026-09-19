<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu4wq-mek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu4wq-mek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-electric-scooter" /></template>
