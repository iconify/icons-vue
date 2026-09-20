<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5lfbgmeg.css';
import '../../css/c/cqafvmdbv.css';
import '../../css/w/whsz71boo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b5lfbgmeg"/><path class="cqafvmdbv"/><path clip-rule="evenodd" class="whsz71boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:screen-duplicate" /></template>
