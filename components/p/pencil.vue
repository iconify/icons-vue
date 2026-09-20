<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp2ooab-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp2ooab-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pencil" /></template>
