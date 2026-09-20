<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkw7-jbie.css';
import '../../css/n/nvnedvrpl.css';
import '../../css/r/r75br4b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkw7-jbie"/><path class="nvnedvrpl"/><path class="r75br4b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:moby" /></template>
