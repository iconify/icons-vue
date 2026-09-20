<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxty1jb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxty1jb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:stackframe-duotone" /></template>
