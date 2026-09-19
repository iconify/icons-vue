<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2g3rbt8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2g3rbt8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:school-xmark-alt-outline" /></template>
