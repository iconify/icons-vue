<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syd7371ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syd7371ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:sun" /></template>
