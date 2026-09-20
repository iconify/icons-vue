<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5fyvxggv.css';
import '../../css/k/k3qeubcag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5fyvxggv"/><path class="k3qeubcag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:tags-refresh-bold" /></template>
