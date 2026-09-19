<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/e/et3i3ja-x.css';
import '../../css/f/fzjlzb7dq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGfRFtuddH"><g class="aql7dnt-u"><path class="et3i3ja-x"/><path class="fzjlzb7dq"/></g></mask></defs><path mask="url(#SVGfRFtuddH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:seedling" /></template>
