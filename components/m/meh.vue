<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utqzt6bcp.css';
import '../../css/b/bymhq5bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utqzt6bcp wm-k"/><path class="bymhq5bkw wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:meh" /></template>
