<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh582hbel.css';
import '../../css/e/e6zc0ccud.css';
import '../../css/b/bvqr90b7l.css';
import '../../css/f/fsaxo7b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eh582hbel"/><path class="e6zc0ccud"/><path class="bvqr90b7l"/><path class="fsaxo7b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:streamlink" /></template>
