<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p74y-9bqn.css';
import '../../css/d/d_twzvgsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p74y-9bqn"/><path class="d_twzvgsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:plus-square" /></template>
