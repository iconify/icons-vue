<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo1tk3-8o.css';
import '../../css/x/x18puqb7i.css';
import '../../css/w/w8jozfhvk.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAlPGBhXj"><g class="zo1tk3-8o"><path class="x18puqb7i"/><path class="w8jozfhvk"/></g></mask></defs><path mask="url(#SVGAlPGBhXj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:vigo" /></template>
