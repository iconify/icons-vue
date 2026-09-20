<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpgv93bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpgv93bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:play-card-8-filled" /></template>
