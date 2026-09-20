<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ansn29b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ansn29b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:oval-vertical" /></template>
