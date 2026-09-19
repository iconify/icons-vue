<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3dh3ypqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p3dh3ypqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:menu-alt-02" /></template>
