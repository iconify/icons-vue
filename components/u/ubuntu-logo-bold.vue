<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh7jieb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh7jieb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:ubuntu-logo-bold" /></template>
