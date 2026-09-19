<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx2_beb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx2_beb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:umbrella-alt-02-filled" /></template>
