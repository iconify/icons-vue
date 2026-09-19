<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j9hg1or3h.css';
import '../../css/y/y1g7ndbcc.css';
import '../../css/v/vpr5xac0l.css';
import '../../css/b/b-nlqbjlj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGiQerUn8u"><g class="v3_i3wktz"><path class="j9hg1or3h"/><path class="y1g7ndbcc"/><path class="vpr5xac0l"/><path class="b-nlqbjlj"/></g></mask></defs><path mask="url(#SVGiQerUn8u)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:museum-two" /></template>
