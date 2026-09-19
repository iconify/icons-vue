<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgga7abld.css';
import '../../css/z/zov5p_f0d.css';
import '../../css/j/jknat6yla.css';
import '../../css/l/lba8bpl1h.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYHjHfc4y"><g class="cgga7abld"><path class="zov5p_f0d"/><path class="jknat6yla"/><path class="lba8bpl1h"/></g></mask></defs><path mask="url(#SVGYHjHfc4y)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:treadmill-one" /></template>
