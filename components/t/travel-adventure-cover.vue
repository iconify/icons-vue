<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu21i6lgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:travel-adventure-cover" /></template>
<style>
.lu21i6lgk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.036 13.702L9.75 8.773V7.421q.322.03.667-.078l.807-.252q.985-.309.985-1.341t-.985-1.341l-.807-.252q-.409-.128-.786-.062q-.051-.079-.12-.144q-.068-.064-.151-.109t-.174-.069Q9.094 3.75 9 3.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v4.295L1.854 19.618q-.104.177-.104.382q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.211 0 .391-.11q.063-.039.117-.089t.098-.109t.075-.127t.048-.139t.02-.146t-.008-.146q-.012-.073-.037-.143q-.026-.069-.064-.132l-5.5-9q-.075-.123-.19-.209q-.059-.044-.126-.076q-.066-.032-.138-.051q-.071-.018-.145-.022t-.147.007t-.143.034q-.07.025-.133.063q-.064.037-.119.087t-.099.108z");
}

</style>
