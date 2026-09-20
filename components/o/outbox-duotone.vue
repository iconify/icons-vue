<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df7pajbkm.css';
import '../../css/n/n6jizwbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="df7pajbkm"/><path class="n6jizwbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:outbox-duotone" /></template>
