<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/c/cdrd5ybzk.css';
import '../../css/b/bypdwpb_f.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGshJT0cSA"><g class="v3_i3wktz"><path class="cdrd5ybzk"/><path class="bypdwpb_f"/></g></mask></defs><path mask="url(#SVGshJT0cSA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:notebook-one" /></template>
