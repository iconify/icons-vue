<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igrpvzb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igrpvzb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:svgo" /></template>
