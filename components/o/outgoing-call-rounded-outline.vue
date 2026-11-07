<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy2l7ab8f.css';
import '../../css/s/s6xf6abum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zy2l7ab8f"/><path class="s6xf6abum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:outgoing-call-rounded-outline" /></template>
