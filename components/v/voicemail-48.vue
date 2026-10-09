<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6id_b8os.css';
import '../../css/g/g-29xb7vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p6id_b8os"/><path class="g-29xb7vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voicemail-48" /></template>
