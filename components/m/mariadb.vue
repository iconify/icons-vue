<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1og6cbek.css';
import '../../css/b/bh-4vfbma.css';
import '../../css/u/u5e77cb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="p1og6cbek"/><path class="bh-4vfbma"/><path clip-rule="evenodd" class="u5e77cb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mariadb" /></template>
