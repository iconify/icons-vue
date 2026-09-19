<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haw94obwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haw94obwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:megaphone" /></template>
