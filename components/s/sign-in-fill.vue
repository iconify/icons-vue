<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy0z5bcpu.css';
import '../../css/o/ol75fg2fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy0z5bcpu"/><path class="ol75fg2fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:sign-in-fill" /></template>
