<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upd0nac5h.css';
import '../../css/z/zce1ctb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="upd0nac5h"/><path class="zce1ctb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nym" /></template>
