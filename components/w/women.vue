<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz-wqstbl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9j4lk5ZG"><path class="iz-wqstbl"/></mask></defs><path mask="url(#SVG9j4lk5ZG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:women" /></template>
