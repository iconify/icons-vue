<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnagsebtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnagsebtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:pen-nib-outline" /></template>
