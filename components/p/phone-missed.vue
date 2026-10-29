<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9xv9fbxk.css';
import '../../css/o/o62a0f6-k.css';
import '../../css/k/key6ijb9f.css';
import '../../css/s/sx9y9xbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9xv9fbxk wm-k"/><path class="o62a0f6-k wm-k"/><path class="key6ijb9f wm-s"/><path class="sx9y9xbyo wm-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:phone-missed" /></template>
