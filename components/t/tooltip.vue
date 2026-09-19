<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujvs38b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujvs38b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:tooltip" /></template>
