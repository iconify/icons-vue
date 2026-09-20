<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcw1c79qb.css';
import '../../css/b/beeg7e7hg.css';
import '../../css/f/fv-cmacjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcw1c79qb"/><path class="beeg7e7hg"/><path class="fv-cmacjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:save-filled" /></template>
