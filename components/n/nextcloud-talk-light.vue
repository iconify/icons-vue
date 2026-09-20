<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5t43yc4z.css';
import '../../css/u/ucpf2webs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="v5t43yc4z"/><path clip-rule="evenodd" class="ucpf2webs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-talk-light" /></template>
