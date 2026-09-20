<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epagx4b5c.css';
import '../../css/o/odq3bckdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epagx4b5c"/><path class="odq3bckdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:power-off" /></template>
