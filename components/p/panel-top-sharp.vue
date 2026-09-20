<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns121jb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns121jb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-top-sharp" /></template>
