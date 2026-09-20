<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qru9siboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qru9siboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:overcast" /></template>
