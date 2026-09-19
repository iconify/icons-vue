<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmujmvhfy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9BO8tGmC"><path class="nmujmvhfy"/></mask></defs><path mask="url(#SVG9BO8tGmC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:tool" /></template>
