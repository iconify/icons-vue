<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bizb7ubav.css';
import '../../css/m/m3tp5udax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bizb7ubav"/><path class="m3tp5udax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:server-sftp-folder" /></template>
