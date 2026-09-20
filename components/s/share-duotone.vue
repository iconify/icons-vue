<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnwldwb2b.css';
import '../../css/n/nuq19qbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnwldwb2b"/><path clip-rule="evenodd" class="nuq19qbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:share-duotone" /></template>
