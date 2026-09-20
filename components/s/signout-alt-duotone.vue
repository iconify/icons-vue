<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sim9l-hfg.css';
import '../../css/e/emjhpkb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sim9l-hfg"/><path class="emjhpkb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:signout-alt-duotone" /></template>
