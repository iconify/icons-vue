<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix7je5b7b.css';
import '../../css/p/pxd2iubby.css';
import '../../css/z/z2rgvhb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix7je5b7b wm-deco"/><path class="pxd2iubby"/><path class="z2rgvhb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:mountain" /></template>
