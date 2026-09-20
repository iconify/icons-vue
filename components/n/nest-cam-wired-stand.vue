<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz8viei-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-cam-wired-stand" /></template>
<style>
.zz8viei-e {
  fill: currentColor;
  d: path("M9.192 21.192q-.329 0-.568-.239q-.24-.24-.24-.568v-1.193q0-1.676 1.175-2.838q1.174-1.162 2.826-1.162q.274 0 .534.035t.529.104l.666-1.042l-2.274-.214q-2.06-.211-3.45-1.735T7 8.75q0-2.071 1.388-3.595T11.84 3.38l3.433-.323q.702-.056 1.227.429q.525.484.525 1.186v8.129q0 .702-.525 1.187q-.525.484-1.227.428l-.025-.019l-.873 1.31q.898.52 1.454 1.432t.555 2.052v1.193q0 .328-.23.568q-.229.24-.577.24z");
}

</style>
