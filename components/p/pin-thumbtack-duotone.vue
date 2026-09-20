<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu1k7ld7a.css';
import '../../css/n/n41378bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu1k7ld7a"/><path clip-rule="evenodd" class="n41378bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pin-thumbtack-duotone" /></template>
