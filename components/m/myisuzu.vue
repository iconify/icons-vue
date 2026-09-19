<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="llk9sh_0f"/><path class="pciuwzd2p"/><path class="qq9fr--dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myisuzu" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.llk9sh_0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.505 30.405h5.993c.43 0 .779-.337.779-.753a.755.755 0 0 0-.527-.712l-5.725-1.896a.747.747 0 0 1-.484-.956a.78.78 0 0 1 .737-.509h5.999m1.297.001v3.695c0 .624.523 1.13 1.17 1.13h3.313c.646 0 1.17-.506 1.17-1.13h0V25.58m9.372 0v3.695c0 .624.523 1.13 1.17 1.13h3.313c.646 0 1.17-.506 1.17-1.13V25.58m-30.05-.001v4.826m23.094 0h-5.993a.766.766 0 0 1-.78-.753c0-.322.212-.608.527-.712l5.725-1.896a.747.747 0 0 0 .485-.956a.78.78 0 0 0-.737-.509h-6m-5.618-6.243v1.933c0 .791-.654 1.433-1.46 1.433h0a1.47 1.47 0 0 1-1.034-.42");
}

.pciuwzd2p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.905 16.972v2.363c0 .792-.654 1.433-1.46 1.433h0c-.808 0-1.462-.641-1.462-1.432v-2.364m-7.776 1.432c0-.79.654-1.432 1.46-1.432h0c.808 0 1.462.641 1.462 1.432v2.364m-2.922-3.796v3.796");
}

.qq9fr--dp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.129 18.404c0-.79.654-1.432 1.46-1.432h0c.808 0 1.462.641 1.462 1.432v2.364");
}

</style>
