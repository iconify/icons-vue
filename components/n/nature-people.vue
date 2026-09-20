<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to_6hw04k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nature-people" /></template>
<style>
.to_6hw04k {
  fill: currentColor;
  d: path("M4.582 12.385q-.482 0-.801-.315t-.32-.796t.315-.801t.797-.32t.8.316t.32.796t-.315.8q-.315.32-.796.32m-.89 9.115v-4h-.769v-3.615q0-.213.144-.357t.356-.143h2.308q.212 0 .356.143t.144.357V17.5h-.77v3h9.116v-6.115h-2.25q-1.371 0-2.31-.93t-.94-2.205q0-1.094.684-1.978q.683-.884 1.75-1.345q.064-1.586 1.157-2.564t2.409-.978t2.409.978t1.156 2.564q1.068.462 1.751 1.345q.684.884.684 1.978q0 1.275-.94 2.205t-2.31.93h-2.25V20.5h5v1z");
}

</style>
