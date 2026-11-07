<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0y-ep3tz.css';
import '../../css/p/ptk9sgbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0y-ep3tz"/><path clip-rule="evenodd" class="ptk9sgbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:screen-share-outline" /></template>
