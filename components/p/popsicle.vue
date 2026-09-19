<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avf981v6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avf981v6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:popsicle" /></template>
