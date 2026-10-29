<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afs_3s29k.css';
import '../../css/g/gp4srle1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afs_3s29k"/><path class="gp4srle1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:trending-down" /></template>
