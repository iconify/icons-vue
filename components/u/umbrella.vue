<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7gfubdlt.css';
import '../../css/l/lrkjd1bsy.css';
import '../../css/l/lriab0bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7gfubdlt wm-a"/><path class="lrkjd1bsy wm-k"/><path class="lriab0bfg wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:umbrella" /></template>
