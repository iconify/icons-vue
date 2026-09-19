<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/y/yy7ol1bks.css';
import '../../css/a/awl6u-98m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxM8OJbya"><g class="hv130ab-t"><path class="yy7ol1bks"/><path class="awl6u-98m"/></g></mask></defs><path mask="url(#SVGxM8OJbya)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:tips-one" /></template>
