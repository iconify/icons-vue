<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-xmtub-r.css';
import '../../css/g/g364_8bya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-xmtub-r"/><path class="g364_8bya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:passkey-fill-24" /></template>
