<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtaw4jumw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtaw4jumw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-forbid-2" /></template>
