<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7wlhvbfe.css';
import '../../css/r/rgmixhqtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7wlhvbfe"/><path class="rgmixhqtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pack-duotone" /></template>
