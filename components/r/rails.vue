<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of88hrgyb.css';
import '../../css/h/hcquu7bpt.css';
import '../../css/y/ys_j6cbby.css';
import '../../css/b/b99j4mbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of88hrgyb"/><path class="hcquu7bpt"/><path class="ys_j6cbby"/><path class="b99j4mbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:rails" /></template>
