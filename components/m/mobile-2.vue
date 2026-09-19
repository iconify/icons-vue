<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj0nwob6o.css';
import '../../css/d/dake0_b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="nj0nwob6o"/><path class="dake0_b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:mobile-2" /></template>
