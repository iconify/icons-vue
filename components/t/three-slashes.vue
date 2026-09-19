<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcy96uaty.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvq0smcdQ"><path class="fcy96uaty"/></mask></defs><path mask="url(#SVGvq0smcdQ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:three-slashes" /></template>
