<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk_ob3kik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk_ob3kik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:veed" /></template>
