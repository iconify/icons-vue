<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa395jbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa395jbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:play-card-star-filled" /></template>
