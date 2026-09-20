<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4wd_7bju.css';
import '../../css/w/wnjg76bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b4wd_7bju"/><path class="wnjg76bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:portainer-pink" /></template>
