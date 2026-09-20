<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp-srlbgu.css';
import '../../css/w/w2xbvabvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bp-srlbgu"/><path class="w2xbvabvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:usulnet" /></template>
