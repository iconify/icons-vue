<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujow3hbno.css';
import '../../css/g/g5c2p-ahz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujow3hbno"/><path class="g5c2p-ahz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notification-remove-outline" /></template>
