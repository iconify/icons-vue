<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l301i3_fe.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8jIuhdOj"><path class="l301i3_fe"/></mask></defs><path mask="url(#SVG8jIuhdOj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:necktie" /></template>
