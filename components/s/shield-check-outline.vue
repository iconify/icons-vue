<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2so5n4so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2so5n4so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:shield-check-outline" /></template>
