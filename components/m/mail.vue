<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7_7ytzqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7_7ytzqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:mail" /></template>
