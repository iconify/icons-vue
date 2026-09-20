<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b27juvnak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b27juvnak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:windicss" /></template>
