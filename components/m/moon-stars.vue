<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3a194bvl.css';
import '../../css/d/dnmle-98o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer w3a194bvl"/><path class="dnmle-98o duoicon-primary-layer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:moon-stars" /></template>
