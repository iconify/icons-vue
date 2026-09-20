<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1mjunbsu.css';
import '../../css/l/lj1vc8a4f.css';
import '../../css/g/gi4a4pb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":501,"height":501};
const content = `<g class="n1mjunbsu"><path class="lj1vc8a4f"/><path class="gi4a4pb7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mattermost-dark" /></template>
