<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d816quf2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d816quf2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:twitch" /></template>
