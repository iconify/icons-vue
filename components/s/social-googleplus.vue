<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3f2lt1bs.css';
import '../../css/x/x720oqwne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u3f2lt1bs"/><path class="x720oqwne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-googleplus" /></template>
