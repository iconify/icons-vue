<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/r/rxf7n0b4j.css';
import '../../css/a/a5u-aqbta.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpxrZpcpf"><g class="aql7dnt-u"><path class="rxf7n0b4j"/><path class="a5u-aqbta"/></g></mask></defs><path mask="url(#SVGpxrZpcpf)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:orange-one" /></template>
