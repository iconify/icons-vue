<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drbld5byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="drbld5byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:stop-outline" /></template>
