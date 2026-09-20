<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-hxxlioz.css';
import '../../css/n/nd5zkmbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-hxxlioz"/><path clip-rule="evenodd" class="nd5zkmbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:mastodon-24" /></template>
