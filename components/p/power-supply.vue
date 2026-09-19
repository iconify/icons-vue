<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/u/u-60abcxg.css';
import '../../css/s/s_6tm9pjp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRv7X7dKS"><g class="aql7dnt-u"><path class="u-60abcxg"/><path class="s_6tm9pjp"/></g></mask></defs><path mask="url(#SVGRv7X7dKS)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:power-supply" /></template>
