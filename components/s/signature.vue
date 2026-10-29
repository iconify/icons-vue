<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz5lihbyw.css';
import '../../css/r/r-5a6yibn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz5lihbyw wm-k"/><path class="r-5a6yibn wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:signature" /></template>
