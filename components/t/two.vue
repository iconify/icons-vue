<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crrxqfb0f.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnTiqDe6y"><path class="crrxqfb0f"/></mask></defs><path mask="url(#SVGnTiqDe6y)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:two" /></template>
