<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctnit8fnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctnit8fnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vonage" /></template>
