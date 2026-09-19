<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sts20cc0v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5oSYUcve"><path class="sts20cc0v"/></mask></defs><path mask="url(#SVG5oSYUcve)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:one" /></template>
